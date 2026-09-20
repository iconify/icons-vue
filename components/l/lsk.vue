<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6oc-mbql.css';
import '../../css/x/x4ukzbcus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6oc-mbql"/><path class="x4ukzbcus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:lsk" /></template>
