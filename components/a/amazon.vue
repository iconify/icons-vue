<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lk1o3d6dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1o3d6dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:amazon" /></template>
