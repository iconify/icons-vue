<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajdm0abav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajdm0abav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-move-up" /></template>
