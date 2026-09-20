<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bz4_77bbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz4_77bbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:godaddy" /></template>
