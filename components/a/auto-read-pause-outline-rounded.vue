<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejuil-m6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-read-pause-outline-rounded" /></template>
<style>
.ejuil-m6n {
  fill: currentColor;
  d: path("M10.665 13.357q.143-.143.143-.357V7q0-.213-.143-.357t-.357-.143t-.357.143T9.808 7v6q0 .214.143.357t.357.143t.357-.143m3.384 0q.143-.143.143-.357V7q0-.213-.143-.357t-.357-.143t-.356.143t-.144.357v6q0 .214.144.357t.356.143t.357-.143M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h14.769q.69 0 1.153.463T21 4.616v10.769q0 .69-.462 1.153T19.385 17zm-.427-1h13.735q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03zM4 16V4z");
}

</style>
