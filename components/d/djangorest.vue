<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc_q9jbdu.css';
import '../../css/c/c5p8reb_m.css';
import '../../css/z/zzxe0-1un.css';
import '../../css/h/h84axl_8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hc_q9jbdu"/><path class="c5p8reb_m"/><path class="zzxe0-1un"/><path class="h84axl_8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:djangorest" /></template>
