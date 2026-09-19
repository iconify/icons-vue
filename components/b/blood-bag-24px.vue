<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt-3h5doh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt-3h5doh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-bag-24px" /></template>
