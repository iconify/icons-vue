<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2t2gy6cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2t2gy6cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:lock-slash" /></template>
