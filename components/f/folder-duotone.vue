<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmytx2b1a.css';
import '../../css/u/us0mlcc8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmytx2b1a"/><path clip-rule="evenodd" class="us0mlcc8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:folder-duotone" /></template>
