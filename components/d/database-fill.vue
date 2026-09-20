<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1h9t2bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1h9t2bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:database-fill" /></template>
