<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p525h4btq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p525h4btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-put-back" /></template>
