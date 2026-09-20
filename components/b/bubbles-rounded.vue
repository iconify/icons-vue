<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cftpwxwpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bubbles-rounded" /></template>
<style>
.cftpwxwpl {
  fill: currentColor;
  d: path("M13.196 13.27L9.37 9.46q-.16-.14-.162-.34q-.003-.202.162-.367q.16-.16.354-.16t.354.16l3.807 3.802v-2.437q0-.213.144-.357q.143-.143.356-.143q.214 0 .357.143t.143.357v3.342q0 .348-.23.578q-.229.23-.577.23h-3.342q-.214 0-.357-.143q-.144-.143-.144-.357t.144-.357t.357-.143zM18.577 19q-1.02 0-1.721-.702t-.702-1.721t.702-1.721t1.721-.702t1.721.702t.702 1.721t-.702 1.721t-1.721.702M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h14.77q.69 0 1.152.463T21 6.616v4.615q0 .213-.143.357t-.357.143t-.357-.143T20 11.23V6.616q0-.27-.173-.443T19.385 6H4.615q-.269 0-.442.173T4 6.616v10.769q0 .269.173.442t.443.173h8.615q.213 0 .357.143t.143.357t-.143.357t-.357.143z");
}

</style>
