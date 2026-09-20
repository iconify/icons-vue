<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bol0cqe0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bol0cqe0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:jfrogbintray" /></template>
