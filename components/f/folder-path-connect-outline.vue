<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4vr5yjnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4vr5yjnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-path-connect-outline" /></template>
