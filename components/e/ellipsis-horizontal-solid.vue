<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia9ptx4wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ia9ptx4wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-horizontal-solid" /></template>
