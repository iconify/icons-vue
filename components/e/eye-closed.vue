<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byy2t7i3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byy2t7i3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:eye-closed" /></template>
