<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl9s-5ban.css';
import '../../css/l/lc9mj6b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl9s-5ban"/><path clip-rule="evenodd" class="lc9mj6b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:book-fill" /></template>
