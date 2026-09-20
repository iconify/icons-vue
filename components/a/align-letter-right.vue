<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spref0m5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spref0m5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:align-letter-right" /></template>
