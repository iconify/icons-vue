<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi0lh-h6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi0lh-h6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lottiefiles-alt" /></template>
