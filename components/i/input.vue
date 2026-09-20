<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktqmhch8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:input" /></template>
<style>
.ktqmhch8q {
  fill: currentColor;
  d: path("M4.616 19q-.691 0-1.153-.462T3 17.384V15.27h1v2.115q0 .231.192.424t.423.192h14.77q.23 0 .423-.192t.192-.424V6.616q0-.231-.192-.424T19.385 6H4.615q-.23 0-.423.192T4 6.616V8.73H3V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v10.769q0 .69-.463 1.153T19.385 19zm7.269-3.577l-.708-.72l2.21-2.203H3v-1h10.387l-2.21-2.204l.708-.719L15.308 12z");
}

</style>
