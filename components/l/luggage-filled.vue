<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-itl9ibz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-itl9ibz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:luggage-filled" /></template>
