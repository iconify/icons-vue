<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_czvyn5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c_czvyn5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-6-sharp-fill" /></template>
