<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbu2q9mrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbu2q9mrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrows-expand" /></template>
