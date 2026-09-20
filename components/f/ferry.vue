<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8amvxbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8amvxbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ferry" /></template>
