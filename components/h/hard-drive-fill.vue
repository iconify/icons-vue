<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj1xpbb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sj1xpbb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:hard-drive-fill" /></template>
