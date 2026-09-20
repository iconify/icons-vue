<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5sdpztvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5sdpztvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-letter-t-filled" /></template>
