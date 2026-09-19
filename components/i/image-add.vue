<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2i8c-38t.css';
import '../../css/v/viznwcc0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2i8c-38t"/><path class="viznwcc0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:image-add" /></template>
