<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b02t79b0o.css';
import '../../css/k/k5cm0iauv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b02t79b0o"/><path class="k5cm0iauv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:couch-filled" /></template>
