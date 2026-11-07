<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsygtybgy.css';
import '../../css/j/jwomz4bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsygtybgy"/><path class="jwomz4bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-left-right-outline" /></template>
