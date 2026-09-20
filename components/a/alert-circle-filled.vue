<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntoj3hb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntoj3hb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:alert-circle-filled" /></template>
