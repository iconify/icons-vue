<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miig5dbtw.css';
import '../../css/d/dp_w-124f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miig5dbtw"/><path class="dp_w-124f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-edit-filled" /></template>
