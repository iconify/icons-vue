<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vivwpdt7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:credit-card-heart-rounded" /></template>
<style>
.vivwpdt7l {
  fill: currentColor;
  d: path("M17.237 19.503q-.137-.053-.268-.184l-2.396-2.396q-.286-.286-.395-.594t-.109-.625q0-.685.479-1.213q.479-.53 1.244-.53q.604 0 .947.278t.796.73q.442-.442.787-.725q.345-.282.955-.282q.79 0 1.257.531q.466.532.466 1.217q0 .317-.121.634t-.383.579L18.1 19.319q-.13.131-.267.184t-.298.053q-.162 0-.298-.053M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v3.92q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357V8.809H4v2.384h8.98q.31 0 .414.304t-.152.506q-1.069.863-1.696 2.146t-.627 2.775q0 .302.024.592q.024.289.091.56q.068.367-.147.646q-.214.279-.562.279z");
}

</style>
