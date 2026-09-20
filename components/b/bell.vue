<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6rw2wb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6rw2wb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:bell" /></template>
