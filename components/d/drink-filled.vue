<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alumgebsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alumgebsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:drink-filled" /></template>
