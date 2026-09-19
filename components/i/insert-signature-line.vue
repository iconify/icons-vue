<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6ky_ifzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v6ky_ifzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:insert-signature-line" /></template>
