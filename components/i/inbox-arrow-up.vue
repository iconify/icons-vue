<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5d26zbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5d26zbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:inbox-arrow-up" /></template>
