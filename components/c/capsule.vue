<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afyho6bfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afyho6bfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:capsule" /></template>
