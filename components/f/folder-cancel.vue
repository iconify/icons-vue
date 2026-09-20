<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqs666f6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqs666f6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:folder-cancel" /></template>
