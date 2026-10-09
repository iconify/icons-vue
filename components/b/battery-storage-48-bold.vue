<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9vsoabzg.css';
import '../../css/v/vj1jlxbvg.css';
import '../../css/s/s24mw7bud.css';
import '../../css/m/mkjr0bxlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b9vsoabzg"/><path class="vj1jlxbvg"/><path class="s24mw7bud"/><path class="mkjr0bxlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-storage-48-bold" /></template>
