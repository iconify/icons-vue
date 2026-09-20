<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzrhttb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzrhttb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:book-line" /></template>
