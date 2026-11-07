<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkzge6j-e.css';
import '../../css/j/jd1l75b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkzge6j-e"/><path class="jd1l75b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:key-square-2-bold" /></template>
