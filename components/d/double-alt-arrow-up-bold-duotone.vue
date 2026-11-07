<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb1na5jao.css';
import '../../css/z/z7rhdcbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb1na5jao"/><path clip-rule="evenodd" class="z7rhdcbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-up-bold-duotone" /></template>
