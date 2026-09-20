<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oijg6cc3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oijg6cc3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clock-hour-4-filled" /></template>
