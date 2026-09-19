<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3wypyb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="s3wypyb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:leaf" /></template>
