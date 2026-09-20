<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/go_38giyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go_38giyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-2-outline" /></template>
