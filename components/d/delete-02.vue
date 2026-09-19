<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3k7hac6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3k7hac6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:delete-02" /></template>
