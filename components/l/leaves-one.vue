<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/ca7yuu_zw.css';
import '../../css/z/z3jh6zbkz.css';
import '../../css/e/e3f4k026v.css';
import '../../css/s/s16_3qbus.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYenE4cOP"><g class="ufeehvblu"><path class="ca7yuu_zw"/><path class="z3jh6zbkz"/><path class="e3f4k026v"/><path class="s16_3qbus"/></g></mask></defs><path mask="url(#SVGYenE4cOP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:leaves-one" /></template>
