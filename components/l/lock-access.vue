<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdaijo30p.css';
import '../../css/j/jevxj9zcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdaijo30p"/><path class="jevxj9zcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:lock-access" /></template>
