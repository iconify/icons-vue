<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8t8n6b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="b8t8n6b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:feather-f" /></template>
