<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgzt6up8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgzt6up8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-bottom-right-filled" /></template>
