<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b30n3eb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b30n3eb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-edit" /></template>
