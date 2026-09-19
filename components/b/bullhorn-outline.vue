<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd9w0yveu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pd9w0yveu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:bullhorn-outline" /></template>
