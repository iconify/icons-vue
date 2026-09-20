<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by7nze-ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="by7nze-ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-no-access-outline" /></template>
