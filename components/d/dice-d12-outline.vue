<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh8uhlb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8uhlb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-d12-outline" /></template>
