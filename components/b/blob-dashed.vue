<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnyw0abwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnyw0abwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:blob-dashed" /></template>
