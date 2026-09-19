<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/m/m799b0buj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnvrPhbjy"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="m799b0buj"/></g></mask></defs><path mask="url(#SVGnvrPhbjy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-text-bottom-one" /></template>
