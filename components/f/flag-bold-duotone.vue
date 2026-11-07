<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq6b85b-a.css';
import '../../css/w/wz-8q9ofo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq6b85b-a"/><path class="wz-8q9ofo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flag-bold-duotone" /></template>
