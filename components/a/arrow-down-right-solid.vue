<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw11da53d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rw11da53d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-down-right-solid" /></template>
