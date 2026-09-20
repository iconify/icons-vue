<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b46rqzb0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b46rqzb0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:laptop" /></template>
