<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/spcy3joli.css';
import '../../css/f/fbt_i58au.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvYKyweds"><g class="ufeehvblu"><path class="spcy3joli"/><path class="fbt_i58au"/></g></mask></defs><path mask="url(#SVGvYKyweds)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:enter-the-keyboard" /></template>
