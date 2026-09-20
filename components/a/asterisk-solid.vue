<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7cdzdb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7cdzdb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:asterisk-solid" /></template>
