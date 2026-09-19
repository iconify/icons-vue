<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo3k9d0ky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo3k9d0ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:eye-off-2-outline" /></template>
