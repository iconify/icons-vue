<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx_eyaasz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx_eyaasz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:layout-bottombar-collapse-filled" /></template>
