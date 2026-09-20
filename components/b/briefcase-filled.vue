<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9l0g5yva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9l0g5yva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:briefcase-filled" /></template>
