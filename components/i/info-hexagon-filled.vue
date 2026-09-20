<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcnq08buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcnq08buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:info-hexagon-filled" /></template>
