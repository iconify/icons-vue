<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-abn8bob.css';
import '../../css/x/xxbq7uh3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-abn8bob"/><path class="xxbq7uh3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-crack-bold-duotone" /></template>
