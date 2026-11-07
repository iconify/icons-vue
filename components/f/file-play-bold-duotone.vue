<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj6gwrmjs.css';
import '../../css/t/to9rn20st.css';
import '../../css/a/a7798gr_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oj6gwrmjs"/><path clip-rule="evenodd" class="to9rn20st"/><path class="a7798gr_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-play-bold-duotone" /></template>
