<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nddaxw3ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nddaxw3ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:hashtag-solid" /></template>
