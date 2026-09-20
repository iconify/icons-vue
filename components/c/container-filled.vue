<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wczcb9hcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wczcb9hcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:container-filled" /></template>
