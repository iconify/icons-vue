<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7jygbgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="sv7jygbgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:adit-profile-with-rocks" /></template>
