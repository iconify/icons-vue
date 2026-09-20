<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzj8564wb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzj8564wb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-discount" /></template>
