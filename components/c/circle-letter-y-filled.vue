<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3fi0wiju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3fi0wiju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-y-filled" /></template>
