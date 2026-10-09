<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy7xqk_um.css';
import '../../css/x/xp2kcen4h.css';
import '../../css/t/tou7l3b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="xp2kcen4h"/><path class="tou7l3b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:film-48-bold" /></template>
