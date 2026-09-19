<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eux2u3jdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eux2u3jdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:format-text" /></template>
