<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzftwlbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzftwlbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:delete-bin-4-fill" /></template>
