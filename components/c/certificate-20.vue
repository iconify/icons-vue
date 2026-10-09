<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fg_sfhb4g.css';
import '../../css/v/vw_qo7apa.css';
import '../../css/b/bsihc0byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fg_sfhb4g"/><path class="vw_qo7apa"/><path class="bsihc0byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:certificate-20" /></template>
