<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/p/p22wnqbnw.css';
import '../../css/f/f1nl8yjrl.css';
import '../../css/q/q9fzk183f.css';
import '../../css/g/g9ouegxjn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSpd8pdZy"><g class="ufeehvblu"><path class="p22wnqbnw"/><path class="f1nl8yjrl"/><path class="q9fzk183f"/><path class="g9ouegxjn"/></g></mask></defs><path mask="url(#SVGSpd8pdZy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bank-card" /></template>
