<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b62_42brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b62_42brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bold" /></template>
