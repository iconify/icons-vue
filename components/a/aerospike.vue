<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64gblb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64gblb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:aerospike" /></template>
