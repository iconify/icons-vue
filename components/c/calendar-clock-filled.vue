<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo3fevbda.css';
import '../../css/g/gz7nuqwbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wo3fevbda"/><path class="gz7nuqwbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:calendar-clock-filled" /></template>
