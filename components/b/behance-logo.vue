<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9vm7jbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9vm7jbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:behance-logo" /></template>
