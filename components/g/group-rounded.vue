<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnla7shci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:group-rounded" /></template>
<style>
.wnla7shci {
  fill: currentColor;
  d: path("M2.596 16.97q0-.697.36-1.198q.361-.5.971-.799q1.3-.621 2.583-.99q1.282-.368 3.086-.368t3.087.369t2.583.989q.609.298.97.799q.36.501.36 1.197v.608q0 .382-.299.71t-.74.328H3.636q-.44 0-.74-.299q-.299-.299-.299-.739zm15.777 1.646q.102-.239.163-.502q.06-.262.06-.537v-.654q0-.87-.353-1.641q-.352-.773-.997-1.324q.737.15 1.42.416t1.35.599q.65.327 1.019.834t.369 1.116v.654q0 .44-.3.74q-.298.298-.738.298zm-10.9-8.108q-.877-.877-.877-2.124q0-1.246.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.124q-.877.876-2.123.876t-2.123-.876m8.516 0q-.877.876-2.123.876q-.064 0-.162-.014t-.162-.032q.502-.627.778-1.38q.276-.754.276-1.574q0-.819-.285-1.563q-.286-.744-.769-1.39q.081-.029.162-.038t.162-.009q1.246 0 2.123.877t.877 2.123t-.877 2.124");
}

</style>
