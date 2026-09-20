<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9t5tfwvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b9t5tfwvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:discord" /></template>
