<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg4806b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:channel-email" /></template>
<style>
.qg4806b_i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75M12 12.05l4.04-3.142q.117-.092.261-.131t.292-.021t.278.092t.221.192q.045.058.078.124q.034.066.053.137q.02.071.025.145t-.004.147t-.032.143q-.024.071-.06.135q-.037.064-.085.12t-.107.101l-4.5 3.5q-.049.038-.103.068q-.055.029-.114.049q-.058.021-.12.031t-.123.01t-.123-.01t-.12-.031q-.059-.02-.114-.049q-.054-.03-.103-.068l-4.5-3.5q-.059-.045-.107-.101t-.085-.12q-.036-.064-.06-.135q-.023-.07-.032-.143t-.004-.147t.025-.145t.053-.137t.078-.124q.092-.118.221-.192q.13-.074.278-.092t.292.021t.261.131z");
}

</style>
