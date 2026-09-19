<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1xdy_u_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1xdy_u_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:crown-filled" /></template>
