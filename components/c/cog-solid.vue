<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g80e41n4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g80e41n4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cog-solid" /></template>
