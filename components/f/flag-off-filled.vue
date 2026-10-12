<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc81pf9ll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc81pf9ll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flag-off-filled" /></template>
