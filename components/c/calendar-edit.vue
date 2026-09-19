<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl7z0xbvn.css';
import '../../css/q/q9j5fk79c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl7z0xbvn"/><path class="q9j5fk79c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:calendar-edit" /></template>
