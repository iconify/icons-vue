<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-k_gnknn.css';
import '../../css/h/hvs5gsb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-k_gnknn"/><path class="hvs5gsb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:letter-opened-bold-duotone" /></template>
