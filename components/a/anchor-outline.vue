<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac2-8hbbw.css';
import '../../css/l/lmsrdu7eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ac2-8hbbw"/><path class="lmsrdu7eq"/><circle class="ac2-8hbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:anchor-outline" /></template>
