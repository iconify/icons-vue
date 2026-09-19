<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrooq11ts.css';
import '../../css/a/apkzo_3wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrooq11ts"/><path class="apkzo_3wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:image-sparkle-filled" /></template>
