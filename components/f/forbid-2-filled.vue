<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7qcaq70w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7qcaq70w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:forbid-2-filled" /></template>
