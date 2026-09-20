<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7rjambcu.css';
import '../../css/a/au92l6bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7rjambcu"/><path class="au92l6bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:anubis" /></template>
