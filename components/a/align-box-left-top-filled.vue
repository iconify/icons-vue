<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqywewn4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqywewn4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-left-top-filled" /></template>
