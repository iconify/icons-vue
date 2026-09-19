<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/k/kufjm8biy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGI03lYb0X"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="kufjm8biy"/></g></mask></defs><path mask="url(#SVGI03lYb0X)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:align-text-center-one" /></template>
