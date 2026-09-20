<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cobpw81wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cobpw81wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ball-pen-fill" /></template>
