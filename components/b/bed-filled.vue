<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aihw6etpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aihw6etpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bed-filled" /></template>
