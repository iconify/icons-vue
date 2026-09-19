<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3y-a-e0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g3y-a-e0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:hand-thumbsdown-fill" /></template>
