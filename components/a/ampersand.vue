<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al1zjj29l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al1zjj29l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ampersand" /></template>
