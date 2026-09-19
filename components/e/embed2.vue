<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj6-xlb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="xj6-xlb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:embed2" /></template>
