<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp3tad87r.css';
import '../../css/h/hbgkxabbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp3tad87r"/><path class="hbgkxabbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cat-body-filled" /></template>
