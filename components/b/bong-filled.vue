<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anu_as0ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anu_as0ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bong-filled" /></template>
