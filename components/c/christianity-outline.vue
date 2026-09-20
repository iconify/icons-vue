<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao2txpbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ao2txpbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:christianity-outline" /></template>
