<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gknx1g06q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gknx1g06q st0"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:brunch" /></template>
