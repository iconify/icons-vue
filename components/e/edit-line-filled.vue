<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yioxj7y0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yioxj7y0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:edit-line-filled" /></template>
